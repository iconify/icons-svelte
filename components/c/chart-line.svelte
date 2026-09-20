<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm59sjb2h.css';
import '../../css/s/sn9k1h9dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm59sjb2h"/><path class="sn9k1h9dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chart-line" {...props}></Icon>
