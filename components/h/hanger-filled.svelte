<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmr98pfdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmr98pfdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hanger-filled" {...props}></Icon>
