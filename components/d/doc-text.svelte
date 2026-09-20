<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp7javlbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lp7javlbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:doc-text" {...props}></Icon>
