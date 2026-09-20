<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6c0kwmfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6c0kwmfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rewind-15s" {...props}></Icon>
