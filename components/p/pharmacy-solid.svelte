<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8uz9rbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c8uz9rbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pharmacy-solid" {...props}></Icon>
