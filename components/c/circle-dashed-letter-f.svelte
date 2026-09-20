<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtevztbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtevztbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-letter-f" {...props}></Icon>
