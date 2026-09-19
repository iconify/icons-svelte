<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_mofebcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y_mofebcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:html5" {...props}></Icon>
