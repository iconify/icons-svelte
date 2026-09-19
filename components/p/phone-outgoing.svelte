<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggljjvbkh.css';
import '../../css/s/s0ff9zwpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggljjvbkh"/><path class="s0ff9zwpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-outgoing" {...props}></Icon>
