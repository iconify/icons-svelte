<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2ylsy7yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w2ylsy7yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-horizontal" {...props}></Icon>
