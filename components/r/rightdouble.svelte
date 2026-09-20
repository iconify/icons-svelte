<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opye0zjue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="opye0zjue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rightdouble" {...props}></Icon>
