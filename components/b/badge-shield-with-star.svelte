<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_aqy6b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q_aqy6b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badge-shield-with-star" {...props}></Icon>
