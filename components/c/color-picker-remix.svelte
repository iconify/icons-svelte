<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_0hgbc0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z_0hgbc0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:color-picker-remix" {...props}></Icon>
