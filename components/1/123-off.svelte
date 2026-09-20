<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_7heqbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_7heqbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:123-off" {...props}></Icon>
