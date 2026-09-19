<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8l94bcrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f8l94bcrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:four-leaves" {...props}></Icon>
