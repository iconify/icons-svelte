<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qej8iv7_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qej8iv7_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-difference-outline" {...props}></Icon>
