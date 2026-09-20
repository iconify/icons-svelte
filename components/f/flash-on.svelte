<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6ekypzqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ekypzqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flash-on" {...props}></Icon>
