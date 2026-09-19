<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf9-5_bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf9-5_bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:appletv-gen2-remote" {...props}></Icon>
