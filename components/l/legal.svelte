<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf8ifdctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1760,"height":1760};
const content = `<path class="mf8ifdctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:legal" {...props}></Icon>
