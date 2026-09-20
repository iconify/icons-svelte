<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o900hie1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o900hie1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-up-1-remix" {...props}></Icon>
