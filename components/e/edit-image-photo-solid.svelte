<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prf4lnbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prf4lnbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:edit-image-photo-solid" {...props}></Icon>
