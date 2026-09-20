<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x25w2h7el.css';
import '../../css/s/s54zkcb4g.css';
import '../../css/y/yipyoybdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x25w2h7el"/><path class="s54zkcb4g"/><path class="yipyoybdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-paginate-filter-music" {...props}></Icon>
