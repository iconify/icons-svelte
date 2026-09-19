<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cap6jo47k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="cap6jo47k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:piwigo" {...props}></Icon>
