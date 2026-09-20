<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w39cyh2fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w39cyh2fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-code-2-solid" {...props}></Icon>
