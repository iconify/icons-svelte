<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhm9hcclm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhm9hcclm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:palette" {...props}></Icon>
