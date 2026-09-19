<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etwiq-3gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="etwiq-3gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-up" {...props}></Icon>
