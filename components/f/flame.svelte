<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2upjwmzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":770,"height":1024};
const content = `<path class="d2upjwmzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flame" {...props}></Icon>
