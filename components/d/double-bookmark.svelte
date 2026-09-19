<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eckk_6b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eckk_6b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:double-bookmark" {...props}></Icon>
