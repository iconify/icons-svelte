<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdznddjex.css';
import '../../css/n/n4fvzrmzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdznddjex"/><path class="n4fvzrmzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-shopping-bags" {...props}></Icon>
