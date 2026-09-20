<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em5g3mbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em5g3mbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-quote-close" {...props}></Icon>
