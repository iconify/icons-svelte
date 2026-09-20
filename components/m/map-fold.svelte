<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yas_40bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yas_40bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:map-fold" {...props}></Icon>
