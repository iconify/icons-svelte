<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-qif68-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-qif68-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop-play" {...props}></Icon>
