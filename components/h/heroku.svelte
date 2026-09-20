<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv24h6bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":284.4};
const content = `<path class="mv24h6bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:heroku" {...props}></Icon>
