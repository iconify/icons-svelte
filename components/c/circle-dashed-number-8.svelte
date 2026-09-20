<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcu_5bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpcu_5bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-8" {...props}></Icon>
