<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rrnwx6buh.css';
import '../../css/p/pr3cdbb2n.css';
import '../../css/e/eq3frqb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rrnwx6buh"/><path class="pr3cdbb2n"/><path class="eq3frqb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-line-linear" {...props}></Icon>
