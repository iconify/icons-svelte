<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_6_n2brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_6_n2brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:corner-up-right" {...props}></Icon>
