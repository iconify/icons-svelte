<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v67cok_4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v67cok_4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-minus" {...props}></Icon>
