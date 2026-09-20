<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_93fbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xz_93fbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:birthday" {...props}></Icon>
