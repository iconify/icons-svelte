<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-64-z-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq-64-z-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-circle-solid" {...props}></Icon>
