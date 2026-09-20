<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy5by7b9g.css';
import '../../css/g/gld9kyb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jy5by7b9g"/><path class="gld9kyb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:medical-library" {...props}></Icon>
