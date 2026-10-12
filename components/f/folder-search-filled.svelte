<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpzeqkffn.css';
import '../../css/s/s7rh6qv0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gpzeqkffn"/><path class="s7rh6qv0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-search-filled" {...props}></Icon>
