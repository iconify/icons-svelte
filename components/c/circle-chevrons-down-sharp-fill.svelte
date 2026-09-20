<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svc3u7xlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svc3u7xlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-down-sharp-fill" {...props}></Icon>
