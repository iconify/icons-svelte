<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9q6m7b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9q6m7b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-4-filled" {...props}></Icon>
