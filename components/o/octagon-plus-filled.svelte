<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2blxh_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us2blxh_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-plus-filled" {...props}></Icon>
