<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk67zg56m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk67zg56m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:medal4-filled" {...props}></Icon>
