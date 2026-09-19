<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veoyribty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veoyribty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:edit-alt-filled" {...props}></Icon>
