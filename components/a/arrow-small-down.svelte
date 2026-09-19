<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhxd_hbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxd_hbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-down" {...props}></Icon>
