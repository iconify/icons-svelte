<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug26ubb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ug26ubb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gold-remix" {...props}></Icon>
