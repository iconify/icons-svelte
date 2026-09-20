<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eprl2eove.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eprl2eove"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:comment-quote-solid" {...props}></Icon>
