<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ejmqqwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ejmqqwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-plus-filled" {...props}></Icon>
