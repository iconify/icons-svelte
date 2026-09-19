<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd-w75bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="fd-w75bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:info" {...props}></Icon>
