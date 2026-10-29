<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvp5xg20i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvp5xg20i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plane" {...props}></Icon>
