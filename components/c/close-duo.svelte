<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks7ou0c8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks7ou0c8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:close-duo" {...props}></Icon>
