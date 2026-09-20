<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlw62wbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlw62wbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:apple" {...props}></Icon>
