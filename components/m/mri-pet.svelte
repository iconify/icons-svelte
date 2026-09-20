<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjvh8st1n.css';
import '../../css/x/xmtno77zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gjvh8st1n"/><path class="xmtno77zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:mri-pet" {...props}></Icon>
