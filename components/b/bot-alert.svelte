<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waeyn_hha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waeyn_hha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-alert" {...props}></Icon>
