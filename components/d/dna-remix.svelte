<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jexeoeb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jexeoeb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dna-remix" {...props}></Icon>
