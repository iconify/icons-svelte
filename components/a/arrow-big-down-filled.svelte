<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7nzfkbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7nzfkbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-big-down-filled" {...props}></Icon>
