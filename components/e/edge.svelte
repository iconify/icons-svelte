<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctb_1j__v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctb_1j__v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:edge" {...props}></Icon>
