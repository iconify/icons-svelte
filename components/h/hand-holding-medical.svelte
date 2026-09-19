<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gox7g7b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gox7g7b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-holding-medical" {...props}></Icon>
