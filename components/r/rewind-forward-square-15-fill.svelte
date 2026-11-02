<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueaz-086o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueaz-086o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-square-15-fill" {...props}></Icon>
