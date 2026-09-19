<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smmzb1bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smmzb1bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:glass" {...props}></Icon>
