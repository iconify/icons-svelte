<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9abhdcbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p9abhdcbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-europe-africa-20-solid" {...props}></Icon>
