<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4ocxdb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4ocxdb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:airplane" {...props}></Icon>
