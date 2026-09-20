<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixxqi91bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixxqi91bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:clock-three" {...props}></Icon>
