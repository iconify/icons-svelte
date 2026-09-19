<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1xd35blt.css';
import '../../css/s/sou039b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f1xd35blt"/><path class="sou039b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-remove" {...props}></Icon>
