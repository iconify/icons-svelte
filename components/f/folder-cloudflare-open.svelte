<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilzbr0e0d.css';
import '../../css/d/d1ok1f99b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ilzbr0e0d"/><path class="d1ok1f99b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cloudflare-open" {...props}></Icon>
