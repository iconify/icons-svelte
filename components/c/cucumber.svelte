<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz4vi98el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":33};
const content = `<path class="qz4vi98el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cucumber" {...props}></Icon>
