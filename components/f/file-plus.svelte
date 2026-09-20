<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4g3jngnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4g3jngnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:file-plus" {...props}></Icon>
