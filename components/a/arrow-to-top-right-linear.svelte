<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmgpwkwdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmgpwkwdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-right-linear" {...props}></Icon>
