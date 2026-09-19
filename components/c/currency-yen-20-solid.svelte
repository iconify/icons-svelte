<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnjluubzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wnjluubzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-yen-20-solid" {...props}></Icon>
