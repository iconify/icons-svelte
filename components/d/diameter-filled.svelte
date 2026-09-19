<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb-_29axf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb-_29axf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:diameter-filled" {...props}></Icon>
