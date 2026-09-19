<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e93v3xb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e93v3xb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:folder-minus" {...props}></Icon>
