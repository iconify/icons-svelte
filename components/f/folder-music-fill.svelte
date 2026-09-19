<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8ca12jyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8ca12jyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-music-fill" {...props}></Icon>
