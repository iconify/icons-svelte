<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giagzkb_z.css';
import '../../css/q/qgd51yb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="giagzkb_z"/><path class="qgd51yb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:left-down" {...props}></Icon>
