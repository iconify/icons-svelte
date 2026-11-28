<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjcgg0b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjcgg0b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:app-window-gear" {...props}></Icon>
