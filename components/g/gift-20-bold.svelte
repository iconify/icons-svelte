<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r56981bwx.css';
import '../../css/o/ol6cddb-q.css';
import '../../css/y/y954mibjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r56981bwx"/><path class="ol6cddb-q"/><path class="y954mibjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gift-20-bold" {...props}></Icon>
