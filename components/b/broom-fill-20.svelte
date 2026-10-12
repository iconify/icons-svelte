<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr2ks5bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vr2ks5bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:broom-fill-20" {...props}></Icon>
