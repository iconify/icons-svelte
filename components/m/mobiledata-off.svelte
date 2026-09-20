<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9m6r4twc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9m6r4twc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mobiledata-off" {...props}></Icon>
