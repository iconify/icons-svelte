<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5maixbua.css';
import '../../css/b/bfq0sui_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5maixbua"/><path class="bfq0sui_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:premier-pro" {...props}></Icon>
