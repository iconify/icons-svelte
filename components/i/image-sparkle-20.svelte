<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ntegbxz.css';
import '../../css/o/oav94mv2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x7ntegbxz"/><path class="oav94mv2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-sparkle-20" {...props}></Icon>
