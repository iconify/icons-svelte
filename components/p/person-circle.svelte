<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj7dqs6bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj7dqs6bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:person-circle" {...props}></Icon>
