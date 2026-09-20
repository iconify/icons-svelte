<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkvmp3jov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fkvmp3jov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-fast-forward-2-solid" {...props}></Icon>
