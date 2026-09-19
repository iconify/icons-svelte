<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/timhajtub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="timhajtub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:iron-two" {...props}></Icon>
