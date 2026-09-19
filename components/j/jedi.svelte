<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm2zggi6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="dm2zggi6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:jedi" {...props}></Icon>
