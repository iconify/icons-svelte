<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeo5czbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oeo5czbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:image-saturation-solid" {...props}></Icon>
