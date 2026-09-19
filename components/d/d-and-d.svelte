<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ksh4r_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="o_ksh4r_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:d-and-d" {...props}></Icon>
