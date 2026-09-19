<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyoj5g2zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qyoj5g2zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:block-four" {...props}></Icon>
