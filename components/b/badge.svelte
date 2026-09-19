<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpodn9pqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpodn9pqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge" {...props}></Icon>
