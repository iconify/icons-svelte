<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il2lrlp5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il2lrlp5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-heart-solid" {...props}></Icon>
