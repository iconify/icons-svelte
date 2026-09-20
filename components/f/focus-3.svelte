<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uujuzybax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uujuzybax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:focus-3" {...props}></Icon>
