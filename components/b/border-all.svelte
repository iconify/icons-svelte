<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-p8ruvaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-p8ruvaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-all" {...props}></Icon>
