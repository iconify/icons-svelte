<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klxp3_jad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="klxp3_jad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:greaterthan-square" {...props}></Icon>
