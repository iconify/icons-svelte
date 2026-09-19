<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnnt3_9du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnnt3_9du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bug-ant" {...props}></Icon>
