<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f85pw7beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f85pw7beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:highlight-off" {...props}></Icon>
