<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-gq3s8at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k-gq3s8at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-4" {...props}></Icon>
