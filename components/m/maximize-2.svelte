<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3wa_vrlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3wa_vrlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:maximize-2" {...props}></Icon>
