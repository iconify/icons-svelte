<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki8ur8pfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ki8ur8pfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:minus-circle" {...props}></Icon>
