<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksec3msnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksec3msnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:face-scan" {...props}></Icon>
