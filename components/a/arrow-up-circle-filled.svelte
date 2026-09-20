<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ag45bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ag45bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-circle-filled" {...props}></Icon>
