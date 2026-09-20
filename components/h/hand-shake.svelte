<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mezhfj8yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mezhfj8yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hand-shake" {...props}></Icon>
