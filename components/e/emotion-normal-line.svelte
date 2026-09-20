<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah_kni4_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ah_kni4_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emotion-normal-line" {...props}></Icon>
