<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8-xbd74t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8-xbd74t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:carrot" {...props}></Icon>
