<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gscn4tkwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gscn4tkwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:config" {...props}></Icon>
