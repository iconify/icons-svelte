<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffd1q6b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffd1q6b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ethereum-circle-solid" {...props}></Icon>
