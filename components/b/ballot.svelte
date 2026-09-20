<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i32j96y3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i32j96y3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ballot" {...props}></Icon>
