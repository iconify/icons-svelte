<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8y__o5bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s8y__o5bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-up-down-20-solid" {...props}></Icon>
