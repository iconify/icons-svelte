<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsf40n85b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsf40n85b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-left-right-filled" {...props}></Icon>
