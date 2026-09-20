<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld_v0xb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ld_v0xb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:checklist" {...props}></Icon>
