<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9i5wjlxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d9i5wjlxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pokeball" {...props}></Icon>
