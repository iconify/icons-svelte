<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze6oqhkxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ze6oqhkxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-bold-left" {...props}></Icon>
