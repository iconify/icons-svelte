<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz11kf90n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz11kf90n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:philippine-peso" {...props}></Icon>
