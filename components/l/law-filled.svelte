<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn3q1jd5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn3q1jd5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:law-filled" {...props}></Icon>
