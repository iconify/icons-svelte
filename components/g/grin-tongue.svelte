<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5wn1cbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u5wn1cbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-tongue" {...props}></Icon>
