<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la7f3abdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la7f3abdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:badge-filled" {...props}></Icon>
