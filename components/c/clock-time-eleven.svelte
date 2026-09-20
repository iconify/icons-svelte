<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv-izabux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv-izabux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-eleven" {...props}></Icon>
