<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6ztnvvyu.css';
import '../../css/g/gf1alnb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t6ztnvvyu"/><path class="gf1alnb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-cutter-20" {...props}></Icon>
