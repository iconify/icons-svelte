<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_6lc6bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_6lc6bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-lightstrip" {...props}></Icon>
