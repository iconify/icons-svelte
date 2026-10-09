<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajd3grb8j.css';
import '../../css/d/dk-jr4bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajd3grb8j"/><path class="dk-jr4bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gallery-20" {...props}></Icon>
