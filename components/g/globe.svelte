<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsz3vzbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsz3vzbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:globe" {...props}></Icon>
