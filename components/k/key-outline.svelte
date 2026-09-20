<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6yaopbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6yaopbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:key-outline" {...props}></Icon>
