<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la5tmqqxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la5tmqqxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aboutdotme" {...props}></Icon>
