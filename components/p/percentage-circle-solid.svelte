<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ac1u1rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2ac1u1rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:percentage-circle-solid" {...props}></Icon>
