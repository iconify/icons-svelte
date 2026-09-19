<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/non-2rb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="non-2rb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:new-twitter" {...props}></Icon>
