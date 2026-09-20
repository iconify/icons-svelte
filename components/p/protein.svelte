<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl_3dwbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl_3dwbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:protein" {...props}></Icon>
