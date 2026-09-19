<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psgz5bp_u.css';
import '../../css/z/z3q3owb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psgz5bp_u"/><path class="z3q3owb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-upload-outline" {...props}></Icon>
