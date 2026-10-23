<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc2xcivwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc2xcivwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:printer" {...props}></Icon>
