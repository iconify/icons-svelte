<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0myofk9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0myofk9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cube-off" {...props}></Icon>
