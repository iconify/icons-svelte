<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj3gj6buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cj3gj6buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:merge-pdf-remix" {...props}></Icon>
