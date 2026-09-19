<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml_qa0sac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml_qa0sac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-receipt" {...props}></Icon>
