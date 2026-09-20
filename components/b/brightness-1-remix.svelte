<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp-u-h4-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tp-u-h4-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-1-remix" {...props}></Icon>
