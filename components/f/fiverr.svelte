<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5j4t1dbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5j4t1dbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fiverr" {...props}></Icon>
