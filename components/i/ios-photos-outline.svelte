<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yup12tbhc.css';
import '../../css/t/txw5etdzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yup12tbhc"/><path class="txw5etdzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-photos-outline" {...props}></Icon>
