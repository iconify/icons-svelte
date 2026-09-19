<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ompabgh.css';
import '../../css/i/il_8vobti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ompabgh"/><path class="il_8vobti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chess" {...props}></Icon>
