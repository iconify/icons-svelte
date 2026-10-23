<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5tg_i0yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5tg_i0yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:banknote-x" {...props}></Icon>
