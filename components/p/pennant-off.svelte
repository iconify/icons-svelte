<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gowbqobyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gowbqobyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pennant-off" {...props}></Icon>
