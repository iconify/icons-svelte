<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3md_prhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u3md_prhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-minus-20-solid" {...props}></Icon>
