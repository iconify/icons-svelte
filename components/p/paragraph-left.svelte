<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyhgcdb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="hyhgcdb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paragraph-left" {...props}></Icon>
