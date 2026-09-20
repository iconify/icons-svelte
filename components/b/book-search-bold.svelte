<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av-303pwd.css';
import '../../css/g/giz0u4e7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av-303pwd"/><path class="giz0u4e7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-search-bold" {...props}></Icon>
