<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asrrilb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asrrilb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-4-fill" {...props}></Icon>
