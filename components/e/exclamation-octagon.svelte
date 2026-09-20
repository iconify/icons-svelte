<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u38ougsmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u38ougsmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:exclamation-octagon" {...props}></Icon>
