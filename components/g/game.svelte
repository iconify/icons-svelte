<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_77_mbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="le_77_mbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:game" {...props}></Icon>
