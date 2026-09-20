<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elp8hoo8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elp8hoo8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:part" {...props}></Icon>
