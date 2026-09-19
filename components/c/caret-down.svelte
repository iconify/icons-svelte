<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl9hx3b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="kl9hx3b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-down" {...props}></Icon>
