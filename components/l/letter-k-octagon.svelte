<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqx5n1fdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqx5n1fdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-octagon" {...props}></Icon>
