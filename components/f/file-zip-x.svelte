<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdzr79dwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdzr79dwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-zip-x" {...props}></Icon>
