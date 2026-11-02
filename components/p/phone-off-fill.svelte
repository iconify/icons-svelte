<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyhfmeb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyhfmeb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-off-fill" {...props}></Icon>
