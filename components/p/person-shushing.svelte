<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clb5el42w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="clb5el42w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-shushing" {...props}></Icon>
