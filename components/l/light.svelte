<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa--x8bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qa--x8bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:light" {...props}></Icon>
