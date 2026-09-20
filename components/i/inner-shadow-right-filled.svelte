<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re2_yqpfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re2_yqpfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-right-filled" {...props}></Icon>
