<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shakr-bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="shakr-bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:phone-arrow-down-left" {...props}></Icon>
