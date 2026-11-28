<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty_q0zb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty_q0zb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-pause" {...props}></Icon>
