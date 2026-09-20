<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmsfnbbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmsfnbbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dice-6-filled" {...props}></Icon>
