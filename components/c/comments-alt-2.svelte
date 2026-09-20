<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y081e11iz.css';
import '../../css/m/m-mridb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="y081e11iz"/><path class="m-mridb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:comments-alt-2" {...props}></Icon>
