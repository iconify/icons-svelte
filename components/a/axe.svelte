<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa2bmhb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wa2bmhb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:axe" {...props}></Icon>
