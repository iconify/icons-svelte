<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khw0c7fxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khw0c7fxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-activity-fill" {...props}></Icon>
