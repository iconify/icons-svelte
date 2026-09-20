<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/havvtcxsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="havvtcxsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:onnx" {...props}></Icon>
