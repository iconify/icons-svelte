<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czys4v05x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czys4v05x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hard-drive-filled" {...props}></Icon>
