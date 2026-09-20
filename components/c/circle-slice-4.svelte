<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8qn1hb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8qn1hb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-slice-4" {...props}></Icon>
