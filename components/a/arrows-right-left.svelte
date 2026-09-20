<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqf_2ftnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqf_2ftnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-right-left" {...props}></Icon>
