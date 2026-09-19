<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mythdnbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mythdnbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:path-unite" {...props}></Icon>
