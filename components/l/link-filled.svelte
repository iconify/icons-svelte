<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t24hzt7cl.css';
import '../../css/j/jel44xajw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t24hzt7cl"/><path class="jel44xajw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:link-filled" {...props}></Icon>
