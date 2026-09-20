<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka1p2wyfl.css';
import '../../css/n/ng_udhb8v.css';
import '../../css/g/g4-q86_8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka1p2wyfl"/><path class="ng_udhb8v"/><path class="g4-q86_8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:home" {...props}></Icon>
