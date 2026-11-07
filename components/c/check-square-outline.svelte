<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h99or5zfb.css';
import '../../css/g/g4e643m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h99or5zfb"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-square-outline" {...props}></Icon>
