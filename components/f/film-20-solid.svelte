<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lup-_0bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lup-_0bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:film-20-solid" {...props}></Icon>
