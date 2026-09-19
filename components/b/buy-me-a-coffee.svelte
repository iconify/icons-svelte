<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgk9v4g2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dgk9v4g2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:buy-me-a-coffee" {...props}></Icon>
