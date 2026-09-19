<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au_eukbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":450,"height":512};
const content = `<path class="au_eukbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jest" {...props}></Icon>
