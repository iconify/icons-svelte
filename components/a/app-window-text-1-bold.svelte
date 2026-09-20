<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8nmi9b7f.css';
import '../../css/l/la22zob0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8nmi9b7f"/><path class="la22zob0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-text-1-bold" {...props}></Icon>
