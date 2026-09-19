<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-xii3aka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="s-xii3aka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flashplayer" {...props}></Icon>
