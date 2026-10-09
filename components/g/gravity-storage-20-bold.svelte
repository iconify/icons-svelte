<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-ahsnbld.css';
import '../../css/w/wc5gufbvx.css';
import '../../css/i/itu8fbbds.css';
import '../../css/v/vjij33b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h-ahsnbld"/><path class="wc5gufbvx"/><path class="itu8fbbds"/><path class="vjij33b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gravity-storage-20-bold" {...props}></Icon>
