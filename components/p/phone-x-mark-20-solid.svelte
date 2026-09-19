<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgxfs0w7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hgxfs0w7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-x-mark-20-solid" {...props}></Icon>
