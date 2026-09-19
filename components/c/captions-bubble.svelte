<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w432bbbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w432bbbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:captions-bubble" {...props}></Icon>
