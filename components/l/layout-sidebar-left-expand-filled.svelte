<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0wqjsb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0wqjsb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-left-expand-filled" {...props}></Icon>
