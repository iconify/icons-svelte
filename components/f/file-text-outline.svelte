<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz_955bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rz_955bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-text-outline" {...props}></Icon>
