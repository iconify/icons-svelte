<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj4wpusjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jj4wpusjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chain" {...props}></Icon>
