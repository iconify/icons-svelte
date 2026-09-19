<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkvprtmov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkvprtmov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:calendar-month-solid" {...props}></Icon>
