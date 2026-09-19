<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2yxpxb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s2yxpxb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:envelope-open-20-solid" {...props}></Icon>
