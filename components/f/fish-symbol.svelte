<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkzyxkb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkzyxkb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fish-symbol" {...props}></Icon>
