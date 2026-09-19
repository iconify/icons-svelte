<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfn9b2zds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xfn9b2zds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:database-export" {...props}></Icon>
