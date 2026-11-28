<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q81twobot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q81twobot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hotel-solid" {...props}></Icon>
