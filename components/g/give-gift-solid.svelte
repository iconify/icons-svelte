<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgxtj0bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rgxtj0bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:give-gift-solid" {...props}></Icon>
