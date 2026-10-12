<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnp2z7g5d.css';
import '../../css/x/x-w7n4-xc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hnp2z7g5d"/><path class="x-w7n4-xc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-bookmark-filled" {...props}></Icon>
