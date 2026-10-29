<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3hzw7iep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3hzw7iep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:quote" {...props}></Icon>
