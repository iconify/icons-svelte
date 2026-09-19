<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azipg_esx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="azipg_esx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:calva" {...props}></Icon>
