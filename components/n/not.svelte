<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-i8abfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gh-i8abfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:not" {...props}></Icon>
