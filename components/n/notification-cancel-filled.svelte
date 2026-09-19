<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhn3e7ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhn3e7ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-cancel-filled" {...props}></Icon>
