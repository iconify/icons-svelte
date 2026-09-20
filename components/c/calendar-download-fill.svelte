<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc82deb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc82deb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-download-fill" {...props}></Icon>
