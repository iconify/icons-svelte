<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3wiavcio.css';
import '../../css/b/bno5nxbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3wiavcio"/><path clip-rule="evenodd" class="bno5nxbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-search-filled" {...props}></Icon>
