<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hex5etblr.css';
import '../../css/m/mfq_7cbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hex5etblr"/><path class="mfq_7cbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:palette" {...props}></Icon>
