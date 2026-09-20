<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daw8iibis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daw8iibis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-minus-outline" {...props}></Icon>
