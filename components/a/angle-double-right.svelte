<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdqco66am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdqco66am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-double-right" {...props}></Icon>
