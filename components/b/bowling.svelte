<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1b7yb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da1b7yb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bowling" {...props}></Icon>
