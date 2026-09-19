<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns35eabmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ns35eabmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:commenting-o" {...props}></Icon>
