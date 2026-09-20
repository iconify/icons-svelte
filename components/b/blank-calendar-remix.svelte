<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4z4x4v0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v4z4x4v0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:blank-calendar-remix" {...props}></Icon>
