<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igsg2zuyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="igsg2zuyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:multiple-stars-remix" {...props}></Icon>
