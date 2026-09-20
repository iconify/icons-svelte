<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3yo1jbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3yo1jbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fossilscm" {...props}></Icon>
