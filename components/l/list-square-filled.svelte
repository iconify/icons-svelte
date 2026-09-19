<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve3cho81o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve3cho81o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-square-filled" {...props}></Icon>
