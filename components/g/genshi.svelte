<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzv_ynb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":310,"height":512};
const content = `<path class="tzv_ynb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:genshi" {...props}></Icon>
