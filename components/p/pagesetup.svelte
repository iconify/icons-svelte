<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imwvrfm9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="imwvrfm9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pagesetup" {...props}></Icon>
