<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohw19ib6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohw19ib6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:polaroid-filled" {...props}></Icon>
