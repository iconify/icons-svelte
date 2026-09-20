<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3djctx0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i3djctx0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:intersex-symbol" {...props}></Icon>
