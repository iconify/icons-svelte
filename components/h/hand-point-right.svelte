<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs48jm-6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zs48jm-6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-point-right" {...props}></Icon>
