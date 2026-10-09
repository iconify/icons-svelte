<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtth2tkbn.css';
import '../../css/i/ikhqytp8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gtth2tkbn"/><path class="ikhqytp8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-card-20-bold" {...props}></Icon>
