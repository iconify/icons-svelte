<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_1zd_p4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u_1zd_p4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:asterisk-stroke-12" {...props}></Icon>
