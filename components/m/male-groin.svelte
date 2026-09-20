<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksh-r617f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ksh-r617f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:male-groin" {...props}></Icon>
