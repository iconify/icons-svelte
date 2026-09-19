<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8ft2lcef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i8ft2lcef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:rdio" {...props}></Icon>
