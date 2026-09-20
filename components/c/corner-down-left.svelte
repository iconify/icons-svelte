<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9ewr3kwo.css';
import '../../css/w/w0fg7jb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ewr3kwo"/><path class="w0fg7jb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:corner-down-left" {...props}></Icon>
