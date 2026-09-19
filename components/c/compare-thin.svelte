<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-s3s_ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-s3s_ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:compare-thin" {...props}></Icon>
