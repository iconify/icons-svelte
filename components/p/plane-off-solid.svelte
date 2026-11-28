<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ldyt6dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-ldyt6dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-off-solid" {...props}></Icon>
