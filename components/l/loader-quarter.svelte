<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu62q_mcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu62q_mcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:loader-quarter" {...props}></Icon>
