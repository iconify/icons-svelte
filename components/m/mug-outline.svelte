<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd2ok_1gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sd2ok_1gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-outline" {...props}></Icon>
