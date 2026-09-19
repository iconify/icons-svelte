<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqnivgadb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqnivgadb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-minus-alt" {...props}></Icon>
