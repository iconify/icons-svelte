<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma4g31zac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma4g31zac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:meeting-point-2" {...props}></Icon>
