<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7mukz4un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7mukz4un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-cross-fill" {...props}></Icon>
