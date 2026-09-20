<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-akw3bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-akw3bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-double-up" {...props}></Icon>
