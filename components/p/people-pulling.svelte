<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybkgz038y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ybkgz038y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:people-pulling" {...props}></Icon>
