<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_xgiebdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_xgiebdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:globe-outline" {...props}></Icon>
