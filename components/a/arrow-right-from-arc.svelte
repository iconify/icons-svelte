<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlmkxu4at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlmkxu4at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-from-arc" {...props}></Icon>
