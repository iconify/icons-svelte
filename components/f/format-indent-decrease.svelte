<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh7g0yt1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh7g0yt1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-indent-decrease" {...props}></Icon>
