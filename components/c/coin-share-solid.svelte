<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0efds0oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o0efds0oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:coin-share-solid" {...props}></Icon>
