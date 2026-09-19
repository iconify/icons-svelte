<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyj01ccef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyj01ccef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye-closed-filled" {...props}></Icon>
