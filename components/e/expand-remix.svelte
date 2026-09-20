<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv9cmca5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sv9cmca5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:expand-remix" {...props}></Icon>
