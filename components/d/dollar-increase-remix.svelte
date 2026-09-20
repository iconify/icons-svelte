<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrc-ynbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wrc-ynbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dollar-increase-remix" {...props}></Icon>
