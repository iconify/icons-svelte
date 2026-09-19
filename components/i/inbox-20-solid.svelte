<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6in-ibdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y6in-ibdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-20-solid" {...props}></Icon>
