<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i51od5bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i51od5bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:clock-solid" {...props}></Icon>
