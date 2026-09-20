<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18t0a4dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c18t0a4dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pagebreak" {...props}></Icon>
