<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbt9z6wse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cbt9z6wse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:flattr" {...props}></Icon>
