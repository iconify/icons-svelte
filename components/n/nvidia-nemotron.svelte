<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqa71qb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqa71qb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nvidia-nemotron" {...props}></Icon>
