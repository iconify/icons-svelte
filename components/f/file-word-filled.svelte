<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp5hn5bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp5hn5bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-word-filled" {...props}></Icon>
