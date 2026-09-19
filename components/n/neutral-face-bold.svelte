<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/istz93bkq.css';
import '../../css/d/d1nyn72ly.css';
import '../../css/y/ylzxxojfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="istz93bkq"/><path class="d1nyn72ly"/><path class="ylzxxojfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:neutral-face-bold" {...props}></Icon>
