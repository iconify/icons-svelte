<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltryvnb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltryvnb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-down" {...props}></Icon>
