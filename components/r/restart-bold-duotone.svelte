<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydoht-zhu.css';
import '../../css/v/v3c_7qboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydoht-zhu"/><path class="v3c_7qboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:restart-bold-duotone" {...props}></Icon>
