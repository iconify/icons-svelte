<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag5uj2ugo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ag5uj2ugo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clock-2-filled" {...props}></Icon>
