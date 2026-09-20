<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7dlc45fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x7dlc45fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:receipt-add-remix" {...props}></Icon>
