<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6v1cwyio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n6v1cwyio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ethereum-circle-remix" {...props}></Icon>
