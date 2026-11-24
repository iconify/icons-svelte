<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfcghdbkz.css';
import '../../css/y/ycfegbxjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="cfcghdbkz"/><path class="ycfegbxjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:passonce" {...props}></Icon>
