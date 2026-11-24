<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzowugs6h.css';
import '../../css/z/zi8cc7b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzowugs6h"/><path class="zi8cc7b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cable-car-filled" {...props}></Icon>
