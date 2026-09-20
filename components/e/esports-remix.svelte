<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nptiocccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nptiocccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:esports-remix" {...props}></Icon>
