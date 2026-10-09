<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bodkpqb0q.css';
import '../../css/p/p3ccqddap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bodkpqb0q"/><path class="p3ccqddap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:audit-20" {...props}></Icon>
