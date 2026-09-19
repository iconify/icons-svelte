<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkk2jqbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkk2jqbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-down-arrow-circle" {...props}></Icon>
