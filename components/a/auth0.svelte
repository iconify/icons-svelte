<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq8y0r2ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aq8y0r2ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:auth0" {...props}></Icon>
