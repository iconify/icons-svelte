<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc-nt5a3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sc-nt5a3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:check" {...props}></Icon>
