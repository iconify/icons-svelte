<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6-jqtiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp6-jqtiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cherry-filled" {...props}></Icon>
