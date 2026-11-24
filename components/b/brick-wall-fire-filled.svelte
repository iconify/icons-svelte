<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu4kwc0bq.css';
import '../../css/h/hc1hzibuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu4kwc0bq"/><path clip-rule="evenodd" class="hc1hzibuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brick-wall-fire-filled" {...props}></Icon>
