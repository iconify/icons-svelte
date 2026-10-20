<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5_uufbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5_uufbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:factory" {...props}></Icon>
