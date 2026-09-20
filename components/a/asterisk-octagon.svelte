<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbv1_z37o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbv1_z37o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-octagon" {...props}></Icon>
