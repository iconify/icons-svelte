<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm5rk2b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm5rk2b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-8" {...props}></Icon>
