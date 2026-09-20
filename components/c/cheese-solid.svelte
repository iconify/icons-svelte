<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3jq4sl8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c3jq4sl8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cheese-solid" {...props}></Icon>
