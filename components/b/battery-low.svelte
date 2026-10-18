<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf5_e-pql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf5_e-pql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-low" {...props}></Icon>
