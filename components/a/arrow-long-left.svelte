<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp9qvac5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pp9qvac5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-long-left" {...props}></Icon>
