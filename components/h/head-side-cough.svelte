<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le4dxjbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="le4dxjbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:head-side-cough" {...props}></Icon>
