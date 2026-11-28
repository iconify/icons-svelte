<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa20cxq8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa20cxq8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:heart-x" {...props}></Icon>
