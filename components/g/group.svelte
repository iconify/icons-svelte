<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysfw4hkul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ysfw4hkul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:group" {...props}></Icon>
