<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msyf_sb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msyf_sb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-lights-fill" {...props}></Icon>
