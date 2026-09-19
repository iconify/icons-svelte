<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_3ttjbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e_3ttjbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:app-notifacation" {...props}></Icon>
