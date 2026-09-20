<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnk28nxih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnk28nxih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:list-ul" {...props}></Icon>
