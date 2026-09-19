<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwu-d8brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kwu-d8brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:database" {...props}></Icon>
