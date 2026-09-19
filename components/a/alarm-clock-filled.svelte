<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngx1zebbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ngx1zebbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:alarm-clock-filled" {...props}></Icon>
