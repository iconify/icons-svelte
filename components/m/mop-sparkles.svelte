<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f--c2tkag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f--c2tkag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mop-sparkles" {...props}></Icon>
