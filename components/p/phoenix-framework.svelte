<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcadknb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kcadknb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phoenix-framework" {...props}></Icon>
