<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhsqqqbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhsqqqbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-spark" {...props}></Icon>
