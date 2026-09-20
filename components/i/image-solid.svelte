<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blhnusbed.css';
import '../../css/j/joyp_jpja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="blhnusbed"/><path clip-rule="evenodd" class="joyp_jpja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-solid" {...props}></Icon>
