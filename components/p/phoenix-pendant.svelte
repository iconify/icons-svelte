<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob12t-xdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob12t-xdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:phoenix-pendant" {...props}></Icon>
