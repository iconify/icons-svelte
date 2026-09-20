<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdex-9bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdex-9bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:forestry" {...props}></Icon>
