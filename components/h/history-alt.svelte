<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2n3k_blu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2n3k_blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:history-alt" {...props}></Icon>
