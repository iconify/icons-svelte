<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdqn2oxjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rdqn2oxjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:quotation-2-solid" {...props}></Icon>
