<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6isgs9fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m6isgs9fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-check-20-solid" {...props}></Icon>
