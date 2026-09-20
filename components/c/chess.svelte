<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uty3owbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uty3owbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chess" {...props}></Icon>
