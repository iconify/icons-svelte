<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw1netl8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw1netl8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:apron-filled" {...props}></Icon>
