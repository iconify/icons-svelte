<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-cro6xfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-cro6xfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:go" {...props}></Icon>
