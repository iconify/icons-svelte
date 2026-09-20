<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pod46obej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pod46obej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:office-building-1-remix" {...props}></Icon>
