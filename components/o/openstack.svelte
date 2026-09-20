<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhw2p6cnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhw2p6cnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openstack" {...props}></Icon>
