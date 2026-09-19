<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwruimg-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="pwruimg-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:headphones" {...props}></Icon>
