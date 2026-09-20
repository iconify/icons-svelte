<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr5mygg-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr5mygg-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-bottom-right-filled" {...props}></Icon>
