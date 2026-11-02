<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir-d2rb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir-d2rb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:passport-fill" {...props}></Icon>
