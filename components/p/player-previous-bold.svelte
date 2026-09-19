<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnvii-tja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnvii-tja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-previous-bold" {...props}></Icon>
