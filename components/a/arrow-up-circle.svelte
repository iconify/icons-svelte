<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thtczq8qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="thtczq8qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-up-circle" {...props}></Icon>
