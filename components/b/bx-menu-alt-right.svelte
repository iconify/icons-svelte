<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcm6c3j0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcm6c3j0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-menu-alt-right" {...props}></Icon>
