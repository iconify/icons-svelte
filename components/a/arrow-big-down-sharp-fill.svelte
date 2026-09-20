<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0w60hbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0w60hbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-down-sharp-fill" {...props}></Icon>
