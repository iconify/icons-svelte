<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/einhko8ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="einhko8ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:escalator-down" {...props}></Icon>
