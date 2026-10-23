<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rolv1m5rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rolv1m5rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:phone-missed" {...props}></Icon>
