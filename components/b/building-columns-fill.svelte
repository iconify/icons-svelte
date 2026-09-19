<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aer2r279m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="aer2r279m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:building-columns-fill" {...props}></Icon>
