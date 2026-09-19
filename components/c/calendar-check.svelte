<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_ef62wo.css';
import '../../css/l/lh-ua9zws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_ef62wo"/><path class="lh-ua9zws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-check" {...props}></Icon>
