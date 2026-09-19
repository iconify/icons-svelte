<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr_qs9ogj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr_qs9ogj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-7-bold" {...props}></Icon>
