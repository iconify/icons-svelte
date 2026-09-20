<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp2r4p57i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp2r4p57i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-right-middle" {...props}></Icon>
