<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj_rtjbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zj_rtjbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-graphics-small-filled" {...props}></Icon>
