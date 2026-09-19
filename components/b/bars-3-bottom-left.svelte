<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb6l9qbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lb6l9qbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-3-bottom-left" {...props}></Icon>
