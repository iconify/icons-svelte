<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or953jb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or953jb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cursor-click-filled" {...props}></Icon>
