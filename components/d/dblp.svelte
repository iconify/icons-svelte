<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kylvxgb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="kylvxgb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:dblp" {...props}></Icon>
