<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj99t9bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj99t9bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrows-up-down" {...props}></Icon>
