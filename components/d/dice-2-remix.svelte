<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyepdbb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tyepdbb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dice-2-remix" {...props}></Icon>
