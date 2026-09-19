<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyscs09jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wyscs09jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-stuck-out-tongue-and-tightly-closed-eyes" {...props}></Icon>
