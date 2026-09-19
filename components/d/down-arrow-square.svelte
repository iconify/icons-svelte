<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq5ltcb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5ltcb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:down-arrow-square" {...props}></Icon>
