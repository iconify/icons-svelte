<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nll5oncab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nll5oncab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pencil-outline" {...props}></Icon>
