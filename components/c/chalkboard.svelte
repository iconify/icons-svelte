<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouojj_bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ouojj_bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chalkboard" {...props}></Icon>
