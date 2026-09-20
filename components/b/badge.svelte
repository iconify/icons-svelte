<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkec0kb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fkec0kb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:badge" {...props}></Icon>
