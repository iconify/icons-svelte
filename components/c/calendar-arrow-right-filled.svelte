<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9svjjhpo.css';
import '../../css/v/v1_dsqc1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9svjjhpo"/><path class="v1_dsqc1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-arrow-right-filled" {...props}></Icon>
