<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t84zvqb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t84zvqb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-vertical" {...props}></Icon>
