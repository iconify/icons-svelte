<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcddw3bvx.css';
import '../../css/i/i3a4j3hes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcddw3bvx"/><path class="i3a4j3hes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-circle-down" {...props}></Icon>
