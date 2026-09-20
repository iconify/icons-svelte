<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grp-vub5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grp-vub5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-filled" {...props}></Icon>
