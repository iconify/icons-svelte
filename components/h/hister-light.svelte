<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yup-t7bvl.css';
import '../../css/m/m0sn3w28b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yup-t7bvl"/><path class="m0sn3w28b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hister-light" {...props}></Icon>
