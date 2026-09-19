<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi9qgerqe.css';
import '../../css/t/t7bnoab5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi9qgerqe"/><path class="t7bnoab5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-chev-right" {...props}></Icon>
