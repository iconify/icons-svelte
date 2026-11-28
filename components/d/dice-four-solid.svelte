<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewmyn8hoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewmyn8hoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dice-four-solid" {...props}></Icon>
