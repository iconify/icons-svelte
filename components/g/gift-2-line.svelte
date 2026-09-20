<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymyvlikmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymyvlikmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gift-2-line" {...props}></Icon>
