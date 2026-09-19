<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmqa5hbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmqa5hbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:restaurant-menu-filled" {...props}></Icon>
