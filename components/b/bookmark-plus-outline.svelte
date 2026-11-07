<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llgjdwb_k.css';
import '../../css/e/egk9jea5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llgjdwb_k"/><path clip-rule="evenodd" class="egk9jea5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-plus-outline" {...props}></Icon>
