<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu2np_b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu2np_b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3" {...props}></Icon>
