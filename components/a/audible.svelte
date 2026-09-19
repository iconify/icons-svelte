<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl7zszbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bl7zszbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:audible" {...props}></Icon>
