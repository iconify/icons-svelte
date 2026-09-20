<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i9psbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2i9psbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:book-24" {...props}></Icon>
