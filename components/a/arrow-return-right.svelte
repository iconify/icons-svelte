<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8o4eqbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8o4eqbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-return-right" {...props}></Icon>
