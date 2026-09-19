<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr2wg2aed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr2wg2aed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ipmi2mqtt" {...props}></Icon>
