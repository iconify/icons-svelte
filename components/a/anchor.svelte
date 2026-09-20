<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bghwhdc7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bghwhdc7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:anchor" {...props}></Icon>
