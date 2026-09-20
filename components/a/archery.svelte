<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlaikz75a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jlaikz75a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:archery" {...props}></Icon>
