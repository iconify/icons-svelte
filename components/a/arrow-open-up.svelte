<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/l/l3xoro.css';
import '../../css/w/witbny.css';
import '../../css/y/yauutu.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c l3xoro"/><path class="a0m25c witbny"/><path class="a0m25c yauutu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-open-up" {...props}></Icon>
