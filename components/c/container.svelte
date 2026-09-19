<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ycjiews.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3ycjiews"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:container" {...props}></Icon>
