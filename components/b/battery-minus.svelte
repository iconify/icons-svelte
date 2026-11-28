<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqd65yb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqd65yb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:battery-minus" {...props}></Icon>
