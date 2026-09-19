<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y51we8bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="y51we8bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-export" {...props}></Icon>
