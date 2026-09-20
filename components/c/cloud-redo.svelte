<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8kr3h9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8kr3h9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-redo" {...props}></Icon>
