<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-qdyxf9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-qdyxf9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-remix" {...props}></Icon>
