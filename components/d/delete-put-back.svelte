<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p525h4btq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p525h4btq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-put-back" {...props}></Icon>
