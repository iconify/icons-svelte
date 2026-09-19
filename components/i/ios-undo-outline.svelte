<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax4xf9blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ax4xf9blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-undo-outline" {...props}></Icon>
