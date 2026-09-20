<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj-nmb40m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj-nmb40m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:notification-alarm-2-remix" {...props}></Icon>
