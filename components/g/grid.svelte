<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojuqj5b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojuqj5b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:grid" {...props}></Icon>
