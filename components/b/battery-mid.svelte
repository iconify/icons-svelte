<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giq6r0irk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giq6r0irk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:battery-mid" {...props}></Icon>
