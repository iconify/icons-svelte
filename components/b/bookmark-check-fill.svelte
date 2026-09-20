<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz28ocrgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz28ocrgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bookmark-check-fill" {...props}></Icon>
