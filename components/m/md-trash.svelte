<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elbyz08-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="elbyz08-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-trash" {...props}></Icon>
