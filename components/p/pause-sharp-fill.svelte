<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxp71vylm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxp71vylm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pause-sharp-fill" {...props}></Icon>
