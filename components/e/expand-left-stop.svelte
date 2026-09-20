<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbsc-5bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsc-5bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-left-stop" {...props}></Icon>
