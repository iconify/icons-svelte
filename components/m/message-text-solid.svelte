<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u69-hex5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u69-hex5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:message-text-solid" {...props}></Icon>
