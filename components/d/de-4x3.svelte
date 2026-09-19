<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4l6eub2n.css';
import '../../css/c/c8caqzgai.css';
import '../../css/u/ug-lui25o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="m4l6eub2n"/><path class="c8caqzgai"/><path class="ug-lui25o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:de-4x3" {...props}></Icon>
