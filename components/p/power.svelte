<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl72jlb_c.css';
import '../../css/n/n6ltouozm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl72jlb_c"/><path class="n6ltouozm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:power" {...props}></Icon>
