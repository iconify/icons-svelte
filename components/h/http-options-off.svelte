<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3r4vrcul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3r4vrcul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-options-off" {...props}></Icon>
