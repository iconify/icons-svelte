<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob7kc6bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ob7kc6bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clock-plus-light" {...props}></Icon>
