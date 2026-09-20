<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9375ab5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n9375ab5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-down-2-solid" {...props}></Icon>
