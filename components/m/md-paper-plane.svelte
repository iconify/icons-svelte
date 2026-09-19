<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wte7h9b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wte7h9b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-paper-plane" {...props}></Icon>
