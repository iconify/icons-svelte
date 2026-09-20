<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz-u_qb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz-u_qb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:danger-octagon-solid" {...props}></Icon>
