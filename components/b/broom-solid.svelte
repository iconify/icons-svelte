<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0nmv6btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0nmv6btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:broom-solid" {...props}></Icon>
