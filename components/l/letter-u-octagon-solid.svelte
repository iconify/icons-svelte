<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wytsss47o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wytsss47o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-u-octagon-solid" {...props}></Icon>
