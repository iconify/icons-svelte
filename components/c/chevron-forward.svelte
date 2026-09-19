<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg_6pjuzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rg_6pjuzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-forward" {...props}></Icon>
