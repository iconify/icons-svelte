<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-w8sbdia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g-w8sbdia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bill-cashless-remix" {...props}></Icon>
