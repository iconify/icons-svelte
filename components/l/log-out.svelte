<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgj84yb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgj84yb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:log-out" {...props}></Icon>
