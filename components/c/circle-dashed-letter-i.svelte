<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqdsvacxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqdsvacxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-i" {...props}></Icon>
