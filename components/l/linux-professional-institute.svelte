<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr9w-81wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr9w-81wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:linux-professional-institute" {...props}></Icon>
