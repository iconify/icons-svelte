<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ustgjj26u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ustgjj26u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:link-1" {...props}></Icon>
