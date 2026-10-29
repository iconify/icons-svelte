<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4x-9acsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4x-9acsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:folder" {...props}></Icon>
