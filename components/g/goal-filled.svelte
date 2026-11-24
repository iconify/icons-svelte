<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx50cdblo.css';
import '../../css/q/qlt_8zq6z.css';
import '../../css/g/gqc9d0bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx50cdblo"/><path class="qlt_8zq6z"/><path class="gqc9d0bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:goal-filled" {...props}></Icon>
