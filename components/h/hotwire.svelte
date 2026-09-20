<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znelxccek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znelxccek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hotwire" {...props}></Icon>
