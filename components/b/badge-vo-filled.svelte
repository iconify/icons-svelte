<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-dcdkx8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-dcdkx8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-vo-filled" {...props}></Icon>
