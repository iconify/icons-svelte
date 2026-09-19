<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y73888bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y73888bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-right-filled" {...props}></Icon>
