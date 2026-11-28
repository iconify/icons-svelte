<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcmkfobzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcmkfobzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-moon" {...props}></Icon>
