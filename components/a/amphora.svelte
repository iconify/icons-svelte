<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbil6abfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbil6abfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:amphora" {...props}></Icon>
