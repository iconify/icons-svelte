<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5r7npblp.css';
import '../../css/y/yxi16mj3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5r7npblp"/><path class="yxi16mj3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:1panel-dark" {...props}></Icon>
