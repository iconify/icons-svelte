<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx26_9q9g.css';
import '../../css/f/fxj5wpbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx26_9q9g"/><path class="fxj5wpbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-bookmark-filled" {...props}></Icon>
