<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysf88hb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysf88hb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-undo-2" {...props}></Icon>
