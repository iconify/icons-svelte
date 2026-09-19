<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxnga2-9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxnga2-9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-pie-outline-24px" {...props}></Icon>
