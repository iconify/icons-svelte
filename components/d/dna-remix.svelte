<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kznzfh34c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kznzfh34c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dna-remix" {...props}></Icon>
