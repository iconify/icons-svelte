<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9kl2ncoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9kl2ncoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-smile" {...props}></Icon>
