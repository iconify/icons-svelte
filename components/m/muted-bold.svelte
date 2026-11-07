<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpjfjpbop.css';
import '../../css/d/dqsya0j4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjfjpbop"/><path class="dqsya0j4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:muted-bold" {...props}></Icon>
