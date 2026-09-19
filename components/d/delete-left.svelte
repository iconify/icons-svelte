<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bchngm2td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bchngm2td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:delete-left" {...props}></Icon>
