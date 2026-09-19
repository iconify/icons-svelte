<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnxh3obsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnxh3obsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-left-circle-filled" {...props}></Icon>
