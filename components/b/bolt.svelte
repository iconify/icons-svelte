<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9lq89byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="q9lq89byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bolt" {...props}></Icon>
