<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0ohrig9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w0ohrig9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-transparent-20-solid" {...props}></Icon>
