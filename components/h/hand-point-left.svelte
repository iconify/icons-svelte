<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmy1u9bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qmy1u9bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hand-point-left" {...props}></Icon>
