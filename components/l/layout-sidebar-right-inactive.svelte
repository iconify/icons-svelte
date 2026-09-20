<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-a80lbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-a80lbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-sidebar-right-inactive" {...props}></Icon>
