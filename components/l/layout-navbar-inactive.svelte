<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwi1r-0my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwi1r-0my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-navbar-inactive" {...props}></Icon>
