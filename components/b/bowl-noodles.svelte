<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af8zbz90e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af8zbz90e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-noodles" {...props}></Icon>
