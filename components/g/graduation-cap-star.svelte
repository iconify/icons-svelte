<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/issb3rb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="issb3rb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:graduation-cap-star" {...props}></Icon>
