<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf_ef62wo.css';
import '../../css/q/qf4j7hobc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf_ef62wo"/><path class="qf4j7hobc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-heart" {...props}></Icon>
