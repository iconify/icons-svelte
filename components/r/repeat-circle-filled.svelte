<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctes0nbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctes0nbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:repeat-circle-filled" {...props}></Icon>
