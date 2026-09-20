<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay2sl4w9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay2sl4w9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:kering" {...props}></Icon>
