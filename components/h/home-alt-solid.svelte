<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv1zpjeyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kv1zpjeyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:home-alt-solid" {...props}></Icon>
