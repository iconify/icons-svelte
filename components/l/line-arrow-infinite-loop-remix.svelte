<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc5f9ceih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vc5f9ceih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-infinite-loop-remix" {...props}></Icon>
