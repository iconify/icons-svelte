<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnbrpubfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnbrpubfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagnostic-desktop-bold" {...props}></Icon>
