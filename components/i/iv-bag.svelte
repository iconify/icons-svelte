<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5lkdbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id5lkdbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:iv-bag" {...props}></Icon>
