<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v78bxlboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v78bxlboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:document-arrow-down" {...props}></Icon>
