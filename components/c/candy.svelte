<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxhop7skf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxhop7skf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:candy" {...props}></Icon>
