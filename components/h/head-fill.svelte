<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ifn1ljn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u8ifn1ljn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:head-fill" {...props}></Icon>
