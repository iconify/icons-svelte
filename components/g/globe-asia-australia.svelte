<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-9lwzflx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a-9lwzflx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:globe-asia-australia" {...props}></Icon>
