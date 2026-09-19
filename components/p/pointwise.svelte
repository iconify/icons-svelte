<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1k-6abdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1k-6abdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pointwise" {...props}></Icon>
