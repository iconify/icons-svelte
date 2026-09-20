<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xshqbbt3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xshqbbt3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:microphone-slash" {...props}></Icon>
