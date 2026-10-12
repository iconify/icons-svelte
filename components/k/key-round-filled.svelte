<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5yxh5_1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5yxh5_1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:key-round-filled" {...props}></Icon>
