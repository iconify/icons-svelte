<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmntw8r6r.css';
import '../../css/p/p5rzzbcho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":9};
const content = `<path class="nmntw8r6r"/><path class="p5rzzbcho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:arrowleft" {...props}></Icon>
