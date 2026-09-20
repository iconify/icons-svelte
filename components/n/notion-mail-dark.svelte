<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq52vybza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jq52vybza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-mail-dark" {...props}></Icon>
