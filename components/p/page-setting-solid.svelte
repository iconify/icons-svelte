<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0uo5wbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e0uo5wbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:page-setting-solid" {...props}></Icon>
