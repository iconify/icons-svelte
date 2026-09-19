<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1ha_-7me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m1ha_-7me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-eleven" {...props}></Icon>
