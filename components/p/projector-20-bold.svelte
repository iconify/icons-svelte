<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al-13db5j.css';
import '../../css/x/xv1e-qb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="al-13db5j"/><path class="xv1e-qb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:projector-20-bold" {...props}></Icon>
