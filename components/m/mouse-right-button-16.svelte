<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2apqubdg.css';
import '../../css/o/oj1zdwuco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d2apqubdg"/><path class="oj1zdwuco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mouse-right-button-16" {...props}></Icon>
