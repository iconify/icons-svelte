<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi-0iegqa.css';
import '../../css/o/o-nkwpb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mi-0iegqa"/><path class="o-nkwpb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:administration" {...props}></Icon>
