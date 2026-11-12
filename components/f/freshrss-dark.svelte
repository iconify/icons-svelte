<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chnb4jbyy.css';
import '../../css/v/vprbqcbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="chnb4jbyy"/><path class="vprbqcbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freshrss-dark" {...props}></Icon>
