<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s282eramm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s282eramm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bread-filled" {...props}></Icon>
