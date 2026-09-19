<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3g6tym6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3g6tym6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:headset-sharp" {...props}></Icon>
