<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcnq08buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcnq08buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:info-hexagon-filled" {...props}></Icon>
