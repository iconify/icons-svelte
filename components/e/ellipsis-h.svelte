<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1vh_fbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1vh_fbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:ellipsis-h" {...props}></Icon>
