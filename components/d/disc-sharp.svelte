<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1bg4hbvb.css';
import '../../css/i/i5e6rm6wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="a1bg4hbvb"/><path class="i5e6rm6wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:disc-sharp" {...props}></Icon>
