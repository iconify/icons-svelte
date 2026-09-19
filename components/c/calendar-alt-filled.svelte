<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6um3cbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6um3cbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-alt-filled" {...props}></Icon>
