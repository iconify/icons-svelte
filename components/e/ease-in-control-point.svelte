<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp3opab4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp3opab4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-in-control-point" {...props}></Icon>
