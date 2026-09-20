<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3ywpbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ob3ywpbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:light-dark" {...props}></Icon>
