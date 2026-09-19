<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj98ljgyw.css';
import '../../css/y/yw3dmeumf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj98ljgyw"/><path class="yw3dmeumf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-save" {...props}></Icon>
