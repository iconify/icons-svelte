<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h002_qdfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h002_qdfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:calendar-days" {...props}></Icon>
