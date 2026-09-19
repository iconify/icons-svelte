<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsetkrwdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsetkrwdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-left-right" {...props}></Icon>
