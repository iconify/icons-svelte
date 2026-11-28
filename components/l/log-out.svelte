<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2zvciboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2zvciboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:log-out" {...props}></Icon>
