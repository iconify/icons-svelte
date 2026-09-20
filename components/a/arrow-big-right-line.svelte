<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot9ksnb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot9ksnb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-right-line" {...props}></Icon>
