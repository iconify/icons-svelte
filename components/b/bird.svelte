<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1uus8zrf.css';
import '../../css/z/zzmml7btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1uus8zrf"/><path class="zzmml7btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bird" {...props}></Icon>
