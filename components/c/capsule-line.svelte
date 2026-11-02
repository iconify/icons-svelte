<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/modzxhp8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="modzxhp8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:capsule-line" {...props}></Icon>
