<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_analbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z_analbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-arrow-up-20-solid" {...props}></Icon>
