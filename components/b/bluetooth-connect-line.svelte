<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9oohr1nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9oohr1nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bluetooth-connect-line" {...props}></Icon>
