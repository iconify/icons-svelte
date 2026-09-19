<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4d1k9bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4d1k9bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-baby" {...props}></Icon>
