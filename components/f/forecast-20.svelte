<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yajgwt04s.css';
import '../../css/l/l5wk8zbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yajgwt04s"/><path class="l5wk8zbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forecast-20" {...props}></Icon>
