<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5_1xv7xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5_1xv7xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:lock-alt-solid" {...props}></Icon>
