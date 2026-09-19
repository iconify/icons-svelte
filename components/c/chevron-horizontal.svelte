<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_ncw9bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_ncw9bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chevron-horizontal" {...props}></Icon>
