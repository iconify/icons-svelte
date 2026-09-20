<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3nkb6-fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i3nkb6-fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:desktop-help-remix" {...props}></Icon>
