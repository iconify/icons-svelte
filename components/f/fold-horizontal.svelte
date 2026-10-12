<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay8hjugra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay8hjugra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:fold-horizontal" {...props}></Icon>
