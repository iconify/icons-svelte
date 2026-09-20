<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j744k2xay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j744k2xay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cube" {...props}></Icon>
