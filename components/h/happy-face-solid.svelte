<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbyw4pyrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jbyw4pyrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:happy-face-solid" {...props}></Icon>
