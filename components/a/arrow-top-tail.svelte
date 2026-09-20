<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or_486byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or_486byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-top-tail" {...props}></Icon>
