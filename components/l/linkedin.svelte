<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8782qb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m8782qb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:linkedin" {...props}></Icon>
