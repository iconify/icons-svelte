<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb2gh7q5f.css';
import '../../css/g/gadlesbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2gh7q5f"/><path clip-rule="evenodd" class="gadlesbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-plus-filled" {...props}></Icon>
