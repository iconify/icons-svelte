<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwnuw_b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwnuw_b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:open-umbrella-remix" {...props}></Icon>
