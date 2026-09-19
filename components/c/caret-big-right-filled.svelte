<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9wiit7df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9wiit7df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-big-right-filled" {...props}></Icon>
