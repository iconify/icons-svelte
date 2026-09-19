<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmlvw01bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":481,"height":512};
const content = `<path class="xmlvw01bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:conan" {...props}></Icon>
