<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr2v7635b.css';
import '../../css/l/lrjrz-r-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr2v7635b"/><path class="lrjrz-r-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:docker" {...props}></Icon>
