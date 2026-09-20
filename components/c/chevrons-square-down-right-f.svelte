<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neueqj5_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="neueqj5_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-down-right-f" {...props}></Icon>
