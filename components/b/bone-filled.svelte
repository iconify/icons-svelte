<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdlu0zubj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdlu0zubj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bone-filled" {...props}></Icon>
