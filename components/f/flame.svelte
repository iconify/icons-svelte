<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnr7hi9rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnr7hi9rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flame" {...props}></Icon>
