<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw_7s7aau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw_7s7aau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:awesomewm" {...props}></Icon>
