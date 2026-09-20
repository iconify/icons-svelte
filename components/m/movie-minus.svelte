<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aizf3somi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aizf3somi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-minus" {...props}></Icon>
