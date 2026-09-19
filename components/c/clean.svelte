<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1zr6vb5v.css';
import '../../css/e/ee-m9bcyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u1zr6vb5v"/><path class="ee-m9bcyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:clean" {...props}></Icon>
