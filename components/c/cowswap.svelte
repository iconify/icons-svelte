<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv4hofbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv4hofbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cowswap" {...props}></Icon>
