<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi_o19b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_o19b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-users-bold" {...props}></Icon>
