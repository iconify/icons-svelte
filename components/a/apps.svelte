<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b63jx1bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b63jx1bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apps" {...props}></Icon>
