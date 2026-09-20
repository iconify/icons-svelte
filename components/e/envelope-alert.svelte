<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmqbzxb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmqbzxb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-alert" {...props}></Icon>
