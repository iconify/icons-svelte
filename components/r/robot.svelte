<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpn1tqbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpn1tqbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:robot" {...props}></Icon>
