<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg14v6-br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg14v6-br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-angry" {...props}></Icon>
