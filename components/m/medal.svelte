<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w480wccdv.css';
import '../../css/k/kgvfx3eho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w480wccdv"/><path class="kgvfx3eho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:medal" {...props}></Icon>
