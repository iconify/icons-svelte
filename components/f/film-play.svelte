<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj2-0-jta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2-0-jta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-play" {...props}></Icon>
