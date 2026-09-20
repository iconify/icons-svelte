<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g20x7-8pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g20x7-8pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flag-bold" {...props}></Icon>
