<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s41z9kb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s41z9kb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:anchor" {...props}></Icon>
