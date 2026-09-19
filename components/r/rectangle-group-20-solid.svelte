<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxeor7b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xxeor7b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-group-20-solid" {...props}></Icon>
