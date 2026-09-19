<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg41evs9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wg41evs9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:dots-circle-horizontal" {...props}></Icon>
