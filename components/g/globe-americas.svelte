<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6v57ysxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n6v57ysxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:globe-americas" {...props}></Icon>
