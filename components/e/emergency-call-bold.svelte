<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwozwebfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hwozwebfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:emergency-call-bold" {...props}></Icon>
