<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzqv24bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mzqv24bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:exclamation-circle" {...props}></Icon>
