<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rot5gv2bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rot5gv2bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-error-remix" {...props}></Icon>
