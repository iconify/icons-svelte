<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c47vcyzsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c47vcyzsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-up-20-solid" {...props}></Icon>
