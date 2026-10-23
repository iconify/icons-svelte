<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efs01ibdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efs01ibdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder-tree" {...props}></Icon>
