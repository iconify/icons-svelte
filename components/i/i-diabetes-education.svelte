<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ownc4obbs.css';
import '../../css/w/w0z-12ljo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ownc4obbs"/><path class="w0z-12ljo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-diabetes-education" {...props}></Icon>
