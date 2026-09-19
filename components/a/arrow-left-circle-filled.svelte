<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz_5soocm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_5soocm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-circle-filled" {...props}></Icon>
