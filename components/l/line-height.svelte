<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st9g-20gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st9g-20gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:line-height" {...props}></Icon>
