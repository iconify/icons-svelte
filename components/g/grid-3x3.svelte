<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o65s8tnxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o65s8tnxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grid-3x3" {...props}></Icon>
