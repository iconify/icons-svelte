<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plyre2wxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plyre2wxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bus-filled" {...props}></Icon>
