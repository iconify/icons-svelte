<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5u3jub2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u5u3jub2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:document-download" {...props}></Icon>
