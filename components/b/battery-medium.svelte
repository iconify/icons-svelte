<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyua1ub1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyua1ub1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery-medium" {...props}></Icon>
