<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipro3nb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ipro3nb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bars-descending-align-left-arrow-down" {...props}></Icon>
