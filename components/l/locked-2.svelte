<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drrty8bwe.css';
import '../../css/l/l4pt34etg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drrty8bwe"/><path clip-rule="evenodd" class="l4pt34etg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:locked-2" {...props}></Icon>
