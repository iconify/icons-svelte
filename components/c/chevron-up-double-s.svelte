<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br1-2ibkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br1-2ibkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-up-double-s" {...props}></Icon>
