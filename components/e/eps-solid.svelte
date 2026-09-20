<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gztvgb2-v.css';
import '../../css/x/xqf3i9bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gztvgb2-v"/><path clip-rule="evenodd" class="xqf3i9bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:eps-solid" {...props}></Icon>
