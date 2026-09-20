<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwib98sin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwib98sin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkbox-unchecked" {...props}></Icon>
