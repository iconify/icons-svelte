<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib9lzd7wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ib9lzd7wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-add-outline" {...props}></Icon>
