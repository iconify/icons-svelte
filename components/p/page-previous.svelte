<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0iol_2th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0iol_2th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-previous" {...props}></Icon>
