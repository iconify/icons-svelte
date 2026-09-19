<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrkfhlbrj.css';
import '../../css/c/c0pcv8b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jrkfhlbrj"/><path class="c0pcv8b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:page-delete" {...props}></Icon>
