<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-cry_4vx.css';
import '../../css/p/p_obrx4cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-cry_4vx"/><path class="p_obrx4cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-bookmark" {...props}></Icon>
