<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg91i5bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg91i5bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:mention" {...props}></Icon>
