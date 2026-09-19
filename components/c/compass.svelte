<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hloo9kbrj.css';
import '../../css/q/qsngmeh5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hloo9kbrj"/><path class="qsngmeh5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:compass" {...props}></Icon>
