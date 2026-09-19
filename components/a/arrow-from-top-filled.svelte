<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx5wrxbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx5wrxbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-from-top-filled" {...props}></Icon>
