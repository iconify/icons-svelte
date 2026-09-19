<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_p8_75bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v_p8_75bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:image-search" {...props}></Icon>
