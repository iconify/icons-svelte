<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_tqjjm9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_tqjjm9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:open-sidebar-alt-outline" {...props}></Icon>
