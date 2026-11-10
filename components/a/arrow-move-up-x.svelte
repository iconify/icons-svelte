<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5l9n7_8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5l9n7_8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-up-x" {...props}></Icon>
