<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lds2ulbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lds2ulbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ring-doorbell" {...props}></Icon>
