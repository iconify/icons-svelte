<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm8myvyyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm8myvyyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bed-linen-alt" {...props}></Icon>
