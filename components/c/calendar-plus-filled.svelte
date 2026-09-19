<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m380hkbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m380hkbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:calendar-plus-filled" {...props}></Icon>
