<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqccwibwr.css';
import '../../css/b/b09xyt_lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqccwibwr"/><path class="b09xyt_lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flame-bold-duotone" {...props}></Icon>
