<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmfmgycje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmfmgycje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fandom-logo-1" {...props}></Icon>
