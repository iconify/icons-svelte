<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffr4accln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffr4accln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:link-share-2-solid" {...props}></Icon>
