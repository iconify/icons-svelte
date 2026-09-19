<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xugfypbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xugfypbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:pencil" {...props}></Icon>
