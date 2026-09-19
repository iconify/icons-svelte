<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuchegb-g.css';
import '../../css/i/izub48k_p.css';
import '../../css/q/qnwimlb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuchegb-g"/><path class="izub48k_p"/><path class="qnwimlb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bear" {...props}></Icon>
