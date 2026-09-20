<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4vks8bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n4vks8bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:outgoing-call" {...props}></Icon>
