<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6qwakbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6qwakbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:deepl" {...props}></Icon>
