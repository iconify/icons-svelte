<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3z3v4axp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="l3z3v4axp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-compact-right" {...props}></Icon>
