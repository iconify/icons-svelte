<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acd640bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="acd640bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-up-square" {...props}></Icon>
