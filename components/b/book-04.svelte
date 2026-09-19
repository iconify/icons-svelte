<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spnh1qxhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spnh1qxhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:book-04" {...props}></Icon>
