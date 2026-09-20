<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrv-p4bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrv-p4bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:check-square-remix" {...props}></Icon>
