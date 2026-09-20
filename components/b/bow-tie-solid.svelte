<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_uzxcyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n1_uzxcyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bow-tie-solid" {...props}></Icon>
