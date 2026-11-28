<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk7b9xbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7b9xbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-heart" {...props}></Icon>
