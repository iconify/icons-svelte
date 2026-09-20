<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgnxe6t6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fgnxe6t6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-at" {...props}></Icon>
