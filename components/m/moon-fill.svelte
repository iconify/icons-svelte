<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6sy1bzy.css';
import '../../css/o/o65zaeisr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd6sy1bzy"/><path class="o65zaeisr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:moon-fill" {...props}></Icon>
