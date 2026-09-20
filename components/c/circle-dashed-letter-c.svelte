<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqwow-b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqwow-b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-c" {...props}></Icon>
