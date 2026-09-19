<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-zzssbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h-zzssbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-left-20-solid" {...props}></Icon>
