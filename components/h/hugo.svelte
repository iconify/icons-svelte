<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlqlogbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":512};
const content = `<path class="vlqlogbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hugo" {...props}></Icon>
