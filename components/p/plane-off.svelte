<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9bj-bciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9bj-bciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plane-off" {...props}></Icon>
