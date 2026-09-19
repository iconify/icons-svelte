<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veg-jkd-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veg-jkd-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:delete-filled" {...props}></Icon>
