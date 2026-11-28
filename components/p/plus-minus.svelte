<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7r11o9ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7r11o9ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plus-minus" {...props}></Icon>
