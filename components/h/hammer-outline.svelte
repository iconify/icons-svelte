<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw6qw7b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bw6qw7b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hammer-outline" {...props}></Icon>
