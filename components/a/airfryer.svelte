<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf20plmyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf20plmyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:airfryer" {...props}></Icon>
