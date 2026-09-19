<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr05f2bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nr05f2bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-down-right-20-solid" {...props}></Icon>
