<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wha5l4bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wha5l4bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-square-filled" {...props}></Icon>
