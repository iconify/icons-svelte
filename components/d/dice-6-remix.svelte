<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2cuv6b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z2cuv6b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dice-6-remix" {...props}></Icon>
