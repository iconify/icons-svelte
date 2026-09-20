<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw7la6btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw7la6btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-minus" {...props}></Icon>
