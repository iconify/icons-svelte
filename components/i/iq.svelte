<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghmw_ccdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghmw_ccdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:iq" {...props}></Icon>
