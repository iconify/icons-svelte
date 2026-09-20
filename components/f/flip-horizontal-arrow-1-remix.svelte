<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1nh9mbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o1nh9mbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flip-horizontal-arrow-1-remix" {...props}></Icon>
