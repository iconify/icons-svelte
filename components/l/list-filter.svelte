<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyum3qkfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyum3qkfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:list-filter" {...props}></Icon>
