<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbsipg4pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbsipg4pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:roadmapdotsh" {...props}></Icon>
