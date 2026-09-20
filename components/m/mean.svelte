<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy6_ilbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy6_ilbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mean" {...props}></Icon>
