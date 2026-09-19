<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s72_n9bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s72_n9bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:phone" {...props}></Icon>
