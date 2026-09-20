<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tryhe-3gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tryhe-3gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:focus-m-bold" {...props}></Icon>
