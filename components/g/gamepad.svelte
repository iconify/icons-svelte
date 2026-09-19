<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_3n_ebhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a_3n_ebhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:gamepad" {...props}></Icon>
