<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y25th20gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y25th20gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:application-add-remix" {...props}></Icon>
