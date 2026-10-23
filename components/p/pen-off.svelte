<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij4z5606a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij4z5606a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pen-off" {...props}></Icon>
