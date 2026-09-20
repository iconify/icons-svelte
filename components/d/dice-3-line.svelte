<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5fnoe3le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5fnoe3le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-3-line" {...props}></Icon>
