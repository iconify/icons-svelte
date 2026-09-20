<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwjwfqq_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bwjwfqq_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:braille-blind-remix" {...props}></Icon>
