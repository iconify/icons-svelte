<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfzhwiyvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfzhwiyvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:octagon-x" {...props}></Icon>
