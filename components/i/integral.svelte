<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6f823bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="l6f823bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:integral" {...props}></Icon>
