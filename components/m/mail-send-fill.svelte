<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofs8utivc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofs8utivc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-send-fill" {...props}></Icon>
