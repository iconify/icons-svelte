<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ico4pibau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ico4pibau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:connector-filled" {...props}></Icon>
